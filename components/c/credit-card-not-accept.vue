<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/liwx7id7y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="liwx7id7y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:credit-card-not-accept" /></template>
