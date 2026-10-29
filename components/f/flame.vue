<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xa_l6hbaj.css';
import '../../css/m/mylxy3b_v.css';
import '../../css/d/d8znebcca.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wm-k xa_l6hbaj"/><path class="mylxy3b_v wm-k"/><path class="d8znebcca wm-a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:flame" /></template>
