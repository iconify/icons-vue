<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/px_rdbcpg.css';
import '../../css/u/u4c45h7qw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="px_rdbcpg"/><path class="u4c45h7qw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:box-3d-minus-fill" /></template>
