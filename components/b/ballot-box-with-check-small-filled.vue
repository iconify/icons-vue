<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gw4exoqzs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="gw4exoqzs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:ballot-box-with-check-small-filled" /></template>
