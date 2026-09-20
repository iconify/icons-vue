<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kd-74fbyn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="kd-74fbyn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:linux-alt-solid" /></template>
