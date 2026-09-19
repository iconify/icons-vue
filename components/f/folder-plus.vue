<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nmmy2rb5f.css';
import '../../css/y/yqu1lvw7w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nmmy2rb5f"/><path class="yqu1lvw7w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:folder-plus" /></template>
