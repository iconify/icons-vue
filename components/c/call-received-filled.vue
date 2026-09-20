<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/ptjbkkucq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ptjbkkucq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:call-received-filled" /></template>
