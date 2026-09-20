<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m6-sa7uud.css';
import '../../css/a/a_ygf-j1c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="m6-sa7uud"/><path class="a_ygf-j1c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:lightning-cable-solid" /></template>
