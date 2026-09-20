<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sxxkm0vum.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="sxxkm0vum"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:barrel" /></template>
