<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sgj6zf-os.css';
import '../../css/d/dif-cubim.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="sgj6zf-os"/><path class="dif-cubim"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:hospital-solid" /></template>
