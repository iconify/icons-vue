<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/peld2mb6r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="peld2mb6r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:cloud-saving-done-02" /></template>
