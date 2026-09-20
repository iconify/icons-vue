<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k3m6vpbhs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="k3m6vpbhs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:folder-refresh-solid" /></template>
