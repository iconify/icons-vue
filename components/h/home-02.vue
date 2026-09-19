<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pkzwowb5b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pkzwowb5b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:home-02" /></template>
