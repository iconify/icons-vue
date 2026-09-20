<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wxv5vzupi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wxv5vzupi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="meteor-icons:coffee" /></template>
