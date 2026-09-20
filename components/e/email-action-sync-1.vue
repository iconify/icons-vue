<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/q/q6jbiqb9i.css';
import '../../css/i/ibz4ckbnw.css';
import '../../css/l/lymq3jdhi.css';
import '../../css/p/pq3vrqqiu.css';
import '../../css/x/x-t_ist5h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="q6jbiqb9i"/><path class="ibz4ckbnw"/><path class="lymq3jdhi"/><path class="pq3vrqqiu"/><path class="x-t_ist5h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:email-action-sync-1" /></template>
