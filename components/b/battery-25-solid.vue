<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/poq28ib5b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="poq28ib5b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:battery-25-solid" /></template>
