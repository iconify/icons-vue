<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/im9n4db7y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="im9n4db7y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:camera-circle-fill" /></template>
