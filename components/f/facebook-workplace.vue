<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dajbc_bbt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dajbc_bbt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:facebook-workplace" /></template>
