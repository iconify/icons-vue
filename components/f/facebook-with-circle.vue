<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e_6afjkun.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="e_6afjkun"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="entypo-social:facebook-with-circle" /></template>
