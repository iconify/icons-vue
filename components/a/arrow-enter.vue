<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/piwl8bbyl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="piwl8bbyl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="proicons:arrow-enter" /></template>
