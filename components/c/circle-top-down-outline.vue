<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/npnjj3bqi.css';
import '../../css/m/m31n_gbkv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="npnjj3bqi"/><path class="m31n_gbkv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:circle-top-down-outline" /></template>
