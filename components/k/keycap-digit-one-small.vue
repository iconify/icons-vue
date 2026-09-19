<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qmlirebgy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="qmlirebgy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:keycap-digit-one-small" /></template>
