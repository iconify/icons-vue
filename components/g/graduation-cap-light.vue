<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z2i_jyi2c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="z2i_jyi2c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:graduation-cap-light" /></template>
