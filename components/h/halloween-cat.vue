<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/szqzdbcks.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="szqzdbcks"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:halloween-cat" /></template>
