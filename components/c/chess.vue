<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aku9edhek.css';
import '../../css/i/il_8vobti.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aku9edhek"/><path class="il_8vobti"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:chess" /></template>
