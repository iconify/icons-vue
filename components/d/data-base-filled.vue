<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fx4vzkb0x.css';
import '../../css/p/p3id4ob0g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fx4vzkb0x"/><path class="p3id4ob0g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:data-base-filled" /></template>
