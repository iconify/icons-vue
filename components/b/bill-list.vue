<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b6wcg9zld.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="b6wcg9zld"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:bill-list" /></template>
