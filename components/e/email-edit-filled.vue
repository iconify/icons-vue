<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gv8w_-9rs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gv8w_-9rs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:email-edit-filled" /></template>
