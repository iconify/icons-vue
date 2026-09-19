<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fk5quyb5i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fk5quyb5i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:donate-blood" /></template>
