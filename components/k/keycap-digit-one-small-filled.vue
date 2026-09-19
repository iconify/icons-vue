<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iv7i-tbsw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="iv7i-tbsw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:keycap-digit-one-small-filled" /></template>
