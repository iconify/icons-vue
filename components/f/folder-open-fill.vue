<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/myf8m65tt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="myf8m65tt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:folder-open-fill" /></template>
