<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v-hlav_un.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":961};
const content = `<path class="v-hlav_un"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:halfstar" /></template>
