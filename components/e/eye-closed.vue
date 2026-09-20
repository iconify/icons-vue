<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zcmho_b6z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zcmho_b6z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:eye-closed" /></template>
