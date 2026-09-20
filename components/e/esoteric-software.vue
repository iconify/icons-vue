<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w92k9abfk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w92k9abfk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:esoteric-software" /></template>
