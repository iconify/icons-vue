<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/ghipagpno.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ghipagpno"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:building-filled" /></template>
