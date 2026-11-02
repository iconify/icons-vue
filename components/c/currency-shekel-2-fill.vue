<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nmv069b-r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nmv069b-r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:currency-shekel-2-fill" /></template>
