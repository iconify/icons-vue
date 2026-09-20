<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b01z6tb3b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="b01z6tb3b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:circle-check-sharp-fill" /></template>
