<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pbtgplpqg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pbtgplpqg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:hammer" /></template>
