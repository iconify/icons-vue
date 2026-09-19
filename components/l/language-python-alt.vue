<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dmnsknblq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":464,"height":424};
const content = `<path class="dmnsknblq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:language-python-alt" /></template>
