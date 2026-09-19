<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aiz7q4bta.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aiz7q4bta"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:chevron-right-small-filled" /></template>
