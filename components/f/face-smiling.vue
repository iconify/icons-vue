<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/omyq3kh2t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="omyq3kh2t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:face-smiling" /></template>
