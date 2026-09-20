<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/becpy5b5f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="becpy5b5f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:etcd" /></template>
