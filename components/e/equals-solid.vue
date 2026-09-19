<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w7y11lbpw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="w7y11lbpw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:equals-solid" /></template>
