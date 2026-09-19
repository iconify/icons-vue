<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q0k_xybbx.css';
import '../../css/x/xxoj21b8d.css';
import '../../css/b/b40jmxusk.css';
import '../../css/k/khrc9wbsk.css';
import '../../css/g/g85knccnw.css';
import '../../css/g/gs4htub8c.css';
import '../../css/q/qflu69b1a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="q0k_xybbx"/><path class="xxoj21b8d"/><path class="b40jmxusk"/><path class="khrc9wbsk"/><circle class="g85knccnw"/><circle class="gs4htub8c"/><circle class="qflu69b1a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-list-outline" /></template>
