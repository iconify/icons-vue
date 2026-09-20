<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ypj6k3bmy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ypj6k3bmy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:dreamstime" /></template>
