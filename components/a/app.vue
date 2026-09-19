<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ezj3qtbki.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="ezj3qtbki"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:app" /></template>
