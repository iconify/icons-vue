<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wuq75jnxs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="wuq75jnxs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:arrow-up-small-solid" /></template>
