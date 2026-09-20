<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kwenk5bhg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kwenk5bhg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:coreldraw" /></template>
