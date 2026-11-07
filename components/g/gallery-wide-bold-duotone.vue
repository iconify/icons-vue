<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bf2z5ab9j.css';
import '../../css/i/iubpiibgw.css';
import '../../css/c/cnfam5b5i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bf2z5ab9j"/><path clip-rule="evenodd" class="iubpiibgw"/><path class="cnfam5b5i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:gallery-wide-bold-duotone" /></template>
