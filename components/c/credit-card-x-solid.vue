<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ixep7l6xi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ixep7l6xi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:credit-card-x-solid" /></template>
