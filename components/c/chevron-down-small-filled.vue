<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a0rgs5y-a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a0rgs5y-a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:chevron-down-small-filled" /></template>
