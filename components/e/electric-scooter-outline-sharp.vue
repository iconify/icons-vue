<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a1l04nbwx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:electric-scooter-outline-sharp" /></template>
<style>
.a1l04nbwx {
  fill: currentColor;
  d: path("M5.108 17.5q-1.039 0-1.766-.728t-.726-1.77t.726-1.771t1.766-.731q.81 0 1.524.505t.937 1.495h6.07q.178-1.777 1.422-3.09q1.243-1.314 2.931-1.545L16.381 2.5h-3.765v-1h4.576l2.02 9.27h-.327q-1.762 0-3.016 1.253q-1.254 1.254-1.254 3.015v.462H7.57q-.223.99-.937 1.495t-1.524.505m1.066-1.441q.442-.442.442-1.059t-.442-1.059t-1.058-.441t-1.06.441q-.44.442-.44 1.059t.44 1.059q.442.441 1.06.441q.617 0 1.058-.441m10.942.751q-.731-.728-.731-1.77t.728-1.77t1.77-.731t1.77.728t.732 1.77t-.729 1.77t-1.769.732t-1.771-.729m2.827-.713q.441-.441.441-1.059t-.44-1.058t-1.06-.442t-1.058.442t-.441 1.058t.441 1.059t1.059.441t1.058-.441m-6.982 6.557l-5.115-2.577h3.385v-1.73l5.115 2.576h-3.384zm5.924-7.615");
}

</style>
