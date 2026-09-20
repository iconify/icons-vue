<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/en8iypeyz.css';
import '../../css/q/qgciedcam.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="en8iypeyz"/><path clip-rule="evenodd" class="qgciedcam"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:lock-circle-solid" /></template>
