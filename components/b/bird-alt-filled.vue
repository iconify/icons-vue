<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bjexghgat.css';
import '../../css/m/mohe2-hat.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bjexghgat"/><path class="mohe2-hat"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:bird-alt-filled" /></template>
