<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pdn_hb7jm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":704,"height":1024};
const content = `<path class="pdn_hb7jm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:bitcoin" /></template>
