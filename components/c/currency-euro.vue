<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lezz7hbxw.css';
import '../../css/b/b4p59kwgz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="duoicon-secondary-layer lezz7hbxw"/><path class="b4p59kwgz duoicon-primary-layer"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="duo-icons:currency-euro" /></template>
