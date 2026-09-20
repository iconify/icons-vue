<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b8qxc_mtr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b8qxc_mtr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:chef-hat-filled" /></template>
