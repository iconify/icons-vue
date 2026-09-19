<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/arx939g8c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="arx939g8c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:keycap-digit-eight-small-filled" /></template>
