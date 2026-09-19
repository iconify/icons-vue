<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lo3hbvbtc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lo3hbvbtc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:door-open" /></template>
