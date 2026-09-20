<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c7gntf5tm.css';
import '../../css/s/sbi9n7bck.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c7gntf5tm"/><path class="sbi9n7bck"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:hubble-exchange" /></template>
