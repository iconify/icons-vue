<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l10w-sbyp.css';
import '../../css/q/qrjc3lvtw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="l10w-sbyp"/><path class="qrjc3lvtw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:bed-double-solid" /></template>
