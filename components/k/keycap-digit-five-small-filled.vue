<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rc806c_2l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="rc806c_2l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:keycap-digit-five-small-filled" /></template>
