<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/attzhvbqz.css';
import '../../css/v/vzeo59nus.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="attzhvbqz"/><path class="vzeo59nus"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:chevrons-right" /></template>
