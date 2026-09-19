<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/acx5opb6r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="acx5opb6r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:dislike-fill" /></template>
