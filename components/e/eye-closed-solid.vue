<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bd75nn-_w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bd75nn-_w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:eye-closed-solid" /></template>
