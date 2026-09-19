<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aezcewbyk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aezcewbyk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:directions-filled" /></template>
