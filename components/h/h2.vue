<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hdur_ohrp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hdur_ohrp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:h2" /></template>
