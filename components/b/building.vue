<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/ts1w9ibpe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ts1w9ibpe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:building" /></template>
