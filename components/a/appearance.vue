<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g4s0jmqnt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="g4s0jmqnt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pajamas:appearance" /></template>
