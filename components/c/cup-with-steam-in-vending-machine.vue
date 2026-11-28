<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g4ro4s-2u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="g4ro4s-2u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:cup-with-steam-in-vending-machine" /></template>
