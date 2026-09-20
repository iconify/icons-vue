<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w18en2iem"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:electric-scooter-rounded" /></template>
<style>
.w18en2iem {
  fill: currentColor;
  d: path("M5.108 17.5q-1.039 0-1.766-.728t-.726-1.77t.726-1.771t1.766-.731q.81 0 1.524.505t.937 1.495h6.07q.178-1.777 1.422-3.09q1.243-1.314 2.931-1.545l-1.515-6.884q-.038-.212-.211-.347q-.174-.134-.385-.134h-2.765q-.213 0-.357-.144t-.143-.357t.143-.356t.357-.143H15.9q.558 0 .996.348q.439.348.57.914l1.667 7.686q.03.121-.047.221q-.079.1-.201.1q-1.748 0-2.944 1.216q-1.195 1.217-1.32 2.729q-.03.34-.274.563q-.243.223-.593.223H7.569q-.223.99-.937 1.495t-1.524.505m12.008-.69q-.731-.728-.731-1.77t.728-1.77t1.77-.731t1.77.728t.732 1.77t-.729 1.77t-1.769.732t-1.771-.729m-4.154 4.113v1.085q0 .22-.19.34t-.407.01l-3.761-1.902q-.137-.081-.107-.23t.188-.149h2.546v-1.085q0-.22.19-.34q.189-.12.406-.01l3.762 1.902q.136.081.106.23t-.187.149z");
}

</style>
