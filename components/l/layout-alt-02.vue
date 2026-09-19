<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v1zjdybnd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="v1zjdybnd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:layout-alt-02" /></template>
