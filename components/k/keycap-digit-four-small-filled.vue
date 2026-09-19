<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bym2xacxs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="bym2xacxs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:keycap-digit-four-small-filled" /></template>
