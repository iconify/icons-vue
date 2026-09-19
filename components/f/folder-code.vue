<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nmmy2rb5f.css';
import '../../css/v/vpsu-p6oc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nmmy2rb5f"/><path class="vpsu-p6oc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:folder-code" /></template>
