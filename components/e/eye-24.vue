<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o-s2teb4v.css';
import '../../css/g/g7z41b4ky.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o-s2teb4v"/><path clip-rule="evenodd" class="g7z41b4ky"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:eye-24" /></template>
