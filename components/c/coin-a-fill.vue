<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/woeg8eetv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="woeg8eetv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:coin-a-fill" /></template>
