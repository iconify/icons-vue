<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gbx6y9vvp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="gbx6y9vvp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:list-layout-solid" /></template>
