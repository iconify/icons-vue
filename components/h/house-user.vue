<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k17b-1bez.css';
import '../../css/f/flaiagb5f.css';
import '../../css/p/pknpwpb5q.css';
import '../../css/b/bpo0h2box.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k17b-1bez"/><path class="flaiagb5f"/><path class="pknpwpb5q"/><path class="bpo0h2box"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uim:house-user" /></template>
