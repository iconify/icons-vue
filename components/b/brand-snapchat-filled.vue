<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lv5yvkbdh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lv5yvkbdh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:brand-snapchat-filled" /></template>
