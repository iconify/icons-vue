<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lgiznbcqx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="lgiznbcqx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-flat:droplet" /></template>
