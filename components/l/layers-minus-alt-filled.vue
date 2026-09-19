<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uvatpob0r.css';
import '../../css/g/g9wb33bax.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uvatpob0r"/><path class="g9wb33bax"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:layers-minus-alt-filled" /></template>
