<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b5ykhjbkf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b5ykhjbkf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:delete" /></template>
