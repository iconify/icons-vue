<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bbrb64pzm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="bbrb64pzm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:language-cyrillic-filled" /></template>
