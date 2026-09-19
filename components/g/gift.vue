<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qw27pzmjy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qw27pzmjy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:gift" /></template>
