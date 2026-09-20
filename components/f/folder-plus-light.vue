<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m14-lebxp.css';
import '../../css/j/j84ijjsgw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m14-lebxp"/><path clip-rule="evenodd" class="j84ijjsgw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:folder-plus-light" /></template>
