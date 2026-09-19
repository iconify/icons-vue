<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/da9mj-b_s.css';
import '../../css/n/neukm1fuz.css';
import '../../css/b/bhbvqjyxk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<rect class="da9mj-b_s"/><rect class="neukm1fuz"/><rect class="bhbvqjyxk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:grid-row-bottom-filled" /></template>
