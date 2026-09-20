<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bont_gb8a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:group-add-outline-sharp" /></template>
<style>
.bont_gb8a {
  fill: currentColor;
  d: path("M12.692 11.335q.552-.589.776-1.364t.224-1.587t-.224-1.586t-.776-1.364q1.135.104 1.875.95q.74.847.74 2t-.74 2t-1.875.95m5 7.281v-1.692q0-.735-.265-1.4t-.838-1.096q1.025.315 1.872.903q.847.587.847 1.593v1.693zm1.616-6.115v-2h-2v-1h2v-2h1v2h2v1h-2v2zM6.569 10.508q-.877-.877-.877-2.123T6.57 6.26t2.123-.877t2.123.877t.877 2.123t-.877 2.124t-2.123.877t-2.123-.877m-4.877 8.108v-1.647q0-.619.36-1.158q.362-.54.971-.838q1.416-.679 2.833-1.018q1.417-.34 2.836-.34t2.837.34t2.833 1.018q.61.298.97.838q.36.539.36 1.158v1.647zm7-8.231q.825 0 1.413-.588t.587-1.412t-.587-1.413t-1.413-.587t-1.412.587t-.588 1.413t.588 1.412t1.412.588m-6 7.23h12v-.646q0-.332-.214-.625q-.214-.292-.593-.494q-1.235-.598-2.546-.916t-2.647-.318t-2.646.318q-1.312.318-2.546.916q-.379.202-.593.494t-.215.625zm6 0");
}

</style>
