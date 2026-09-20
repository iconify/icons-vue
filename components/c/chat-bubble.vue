<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/plg9hea-n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="plg9hea-n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="radix-icons:chat-bubble" /></template>
