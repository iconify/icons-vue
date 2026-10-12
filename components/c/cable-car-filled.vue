<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vzowugs6h.css';
import '../../css/y/yz3e6tb8u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vzowugs6h"/><path class="yz3e6tb8u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:cable-car-filled" /></template>
