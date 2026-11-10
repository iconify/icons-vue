<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ozi-5urnk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ozi-5urnk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:jellyfish" /></template>
