<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nq--4rb2u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":25,"height":25};
const content = `<path class="nq--4rb2u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:dollar" /></template>
