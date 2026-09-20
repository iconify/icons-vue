<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ygkuqrsls"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:call-log-rounded" /></template>
<style>
.ygkuqrsls {
  fill: currentColor;
  d: path("M17.93 21q-2.528 0-5.184-1.266t-4.944-3.555q-2.27-2.288-3.536-4.935T3 6.07q0-.45.3-.76T4.05 5h2.473q.408 0 .712.257q.303.257.411.659L8.142 8.3q.07.42-.025.733t-.333.513l-2.193 2.046q.615 1.117 1.36 2.076t1.59 1.817q.87.87 1.875 1.62q1.003.749 2.203 1.414l2.139-2.177q.244-.263.549-.347t.674-.033l2.104.43q.407.1.661.411t.254.712v2.435q0 .45-.31.75t-.76.3M12.5 4q-.213 0-.357-.143T12 3.5t.143-.357T12.5 3h8q.214 0 .357.143T21 3.5t-.143.357T20.5 4zm0 3.385q-.213 0-.357-.144T12 6.885t.143-.357t.357-.143h8q.214 0 .357.143t.143.357t-.143.356t-.357.144zm0 3.384q-.213 0-.357-.143T12 10.269t.143-.357t.357-.143h8q.214 0 .357.143t.143.357t-.143.357t-.357.143z");
}

</style>
