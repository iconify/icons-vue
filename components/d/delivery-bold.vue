<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ng9-olbui.css';
import '../../css/s/s8d1qvbbx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ng9-olbui"/><path class="s8d1qvbbx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:delivery-bold" /></template>
