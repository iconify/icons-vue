<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qz4027bss.css';
import '../../css/h/hdke9bc-g.css';
import '../../css/p/pvl81kbjy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qz4027bss wm-a"/><path class="hdke9bc-g wm-k"/><path class="pvl81kbjy wm-k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:headphones" /></template>
