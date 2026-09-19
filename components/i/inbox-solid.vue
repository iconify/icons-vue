<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/abat7y6yz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="abat7y6yz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:inbox-solid" /></template>
