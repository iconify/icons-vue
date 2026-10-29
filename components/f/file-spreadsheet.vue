<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx94fvtdi.css';
import '../../css/j/j-rz0kfnd.css';
import '../../css/b/bq07eo2pj.css';
import '../../css/b/bjpkh6bgj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jx94fvtdi wm-k"/><path class="j-rz0kfnd wm-a"/><path class="bq07eo2pj wm-a"/><path class="bjpkh6bgj wm-k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:file-spreadsheet" /></template>
