<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g-9fnb75y.css';
import '../../css/l/ls5757boo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g-9fnb75y"/><path class="ls5757boo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:folder-unlocked-filled" /></template>
