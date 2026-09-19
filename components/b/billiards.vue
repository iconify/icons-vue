<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gjp3m3bor.css';
import '../../css/t/tn3ef2i2f.css';
import '../../css/b/b2fgv7b-a.css';
import '../../css/w/we48irbvn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="gjp3m3bor"/><path class="tn3ef2i2f"/><path class="b2fgv7b-a"/><path class="we48irbvn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:billiards" /></template>
