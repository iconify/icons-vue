<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tl2db7o2o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="tl2db7o2o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:email-forward-filled" /></template>
