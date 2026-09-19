<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dgt5jg9jy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":768,"height":1024};
const content = `<path class="dgt5jg9jy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:breakable" /></template>
