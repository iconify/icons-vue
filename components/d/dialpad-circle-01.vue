<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mbwrsq0kl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mbwrsq0kl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:dialpad-circle-01" /></template>
