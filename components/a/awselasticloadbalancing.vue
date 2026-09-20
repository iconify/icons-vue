<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cojc1hb-h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cojc1hb-h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:awselasticloadbalancing" /></template>
