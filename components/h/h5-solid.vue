<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/or1fcgb_c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="or1fcgb_c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:h5-solid" /></template>
