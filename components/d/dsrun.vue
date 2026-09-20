<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/duyij83lt.css';
import '../../css/s/snztlmsub.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="duyij83lt"/><path class="snztlmsub"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:dsrun" /></template>
