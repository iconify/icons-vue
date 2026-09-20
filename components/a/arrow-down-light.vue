<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/ss7a92bzj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ss7a92bzj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:arrow-down-light" /></template>
